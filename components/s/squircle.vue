<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii2_-nb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2_-nb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:squircle" /></template>
