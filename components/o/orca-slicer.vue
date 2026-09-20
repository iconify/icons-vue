<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsp5lfbpe.css';
import '../../css/i/ihbuegbvc.css';
import '../../css/i/iiu61dcee.css';
import '../../css/h/hydphr__h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsp5lfbpe"/><path class="ihbuegbvc"/><path class="iiu61dcee"/><path class="hydphr__h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orca-slicer" /></template>
