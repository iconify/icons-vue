<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc15x1w_o.css';
import '../../css/s/scnvldbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc15x1w_o"/><path class="scnvldbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zoom-in-24" /></template>
