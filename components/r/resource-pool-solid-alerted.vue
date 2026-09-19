<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_2i5mwhi.css';
import '../../css/s/skfl9zkqt.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted j_2i5mwhi"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted skfl9zkqt"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:resource-pool-solid-alerted" /></template>
