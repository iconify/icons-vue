<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbj59bi2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbj59bi2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:translate-solid" /></template>
