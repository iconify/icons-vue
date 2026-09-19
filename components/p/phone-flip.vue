<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqnpvm_tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqnpvm_tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:phone-flip" /></template>
