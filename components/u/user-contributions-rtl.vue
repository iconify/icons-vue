<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkto-2bwr.css';
import '../../css/x/x_lnf_bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bkto-2bwr"/><circle class="x_lnf_bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-contributions-rtl" /></template>
