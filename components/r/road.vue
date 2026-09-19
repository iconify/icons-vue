<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hor9gzzrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hor9gzzrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:road" /></template>
