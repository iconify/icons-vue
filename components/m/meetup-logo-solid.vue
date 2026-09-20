<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi105ybas.css';
import '../../css/c/cp_8-04cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi105ybas"/><path class="cp_8-04cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:meetup-logo-solid" /></template>
