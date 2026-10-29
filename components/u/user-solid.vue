<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2j9agbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2j9agbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-solid" /></template>
