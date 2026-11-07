<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvlgxcc0y.css';
import '../../css/k/kzq8r7vcj.css';
import '../../css/i/ie_i89bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvlgxcc0y"/><path class="kzq8r7vcj"/><path clip-rule="evenodd" class="ie_i89bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-plus-rounded-outline" /></template>
