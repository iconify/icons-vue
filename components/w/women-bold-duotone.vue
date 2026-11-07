<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxisibaw.css';
import '../../css/e/ejfpiglxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ejfpiglxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:women-bold-duotone" /></template>
