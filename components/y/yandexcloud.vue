<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trq2iybup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trq2iybup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:yandexcloud" /></template>
