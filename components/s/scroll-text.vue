<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prsaaacnj.css';
import '../../css/x/xvgir7w9l.css';
import '../../css/r/r84512iun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prsaaacnj wm-k"/><path class="wm-k xvgir7w9l"/><path class="r84512iun wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:scroll-text" /></template>
