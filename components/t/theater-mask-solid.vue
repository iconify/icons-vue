<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsn_sqeph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsn_sqeph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:theater-mask-solid" /></template>
