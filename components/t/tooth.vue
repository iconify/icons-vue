<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_nmu6baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_nmu6baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:tooth" /></template>
