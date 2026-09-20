<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr6lwtbkj.css';
import '../../css/y/ymdjnobca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nr6lwtbkj"/><path class="ymdjnobca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:no-smoking" /></template>
