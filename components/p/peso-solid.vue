<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbeam29lh.css';
import '../../css/d/dubmsacdp.css';
import '../../css/l/l7dlcxybl.css';
import '../../css/y/ylf1gbb8r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 jbeam29lh"/><path class="clr-i-solid clr-i-solid-path-2 dubmsacdp"/><path class="clr-i-solid clr-i-solid-path-3 l7dlcxybl"/><path class="clr-i-solid clr-i-solid-path-4 ylf1gbb8r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:peso-solid" /></template>
