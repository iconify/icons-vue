<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltmjp_5as.css';
import '../../css/g/gs4dp93ml.css';
import '../../css/f/f_ydpsblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmjp_5as"/><path class="gs4dp93ml"/><path class="f_ydpsblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-all-filled" /></template>
