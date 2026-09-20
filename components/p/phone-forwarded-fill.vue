<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6valsw2k.css';
import '../../css/y/ypft5mbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6valsw2k"/><path class="ypft5mbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-forwarded-fill" /></template>
