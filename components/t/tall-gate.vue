<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glfvk6b0w.css';
import '../../css/k/kbmuw8bfw.css';
import '../../css/j/jxi6a_dgv.css';
import '../../css/g/g7f4pbc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="glfvk6b0w"/><path class="kbmuw8bfw"/><path class="jxi6a_dgv"/><path class="g7f4pbc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tall-gate" /></template>
