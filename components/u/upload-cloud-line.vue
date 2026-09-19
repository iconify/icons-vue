<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5j-txj5n.css';
import '../../css/q/qga2a08ds.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 h5j-txj5n"/><path class="clr-i-outline clr-i-outline-path-2 qga2a08ds"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:upload-cloud-line" /></template>
