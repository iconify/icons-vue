<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8_af5qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="ae8_af5qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:yandex" /></template>
