<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqod05bbx.css';
import '../../css/l/lo6iqdbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qqod05bbx"/><path class="lo6iqdbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:systemd" /></template>
