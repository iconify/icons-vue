<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwk5qtb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vwk5qtb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:person-walking-duotone" /></template>
