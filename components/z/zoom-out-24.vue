<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4_lrfb5n.css';
import '../../css/s/scnvldbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_lrfb5n"/><path class="scnvldbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zoom-out-24" /></template>
