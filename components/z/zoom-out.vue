<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgnd9bw0t.css';
import '../../css/b/bh1hcdbms.css';
import '../../css/g/g2k-h2zlv.css';
import '../../css/h/h9-ebutrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgnd9bw0t wm-a"/><path class="bh1hcdbms wm-k"/><path class="g2k-h2zlv wm-a"/><path class="h9-ebutrh wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:zoom-out" /></template>
