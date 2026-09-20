<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skvj_eznm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="skvj_eznm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:security-signal" /></template>
