<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm51gobgi.css';
import '../../css/t/tz-ovhbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tm51gobgi"/><circle class="tz-ovhbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:question-mark-fill-12" /></template>
