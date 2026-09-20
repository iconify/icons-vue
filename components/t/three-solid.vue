<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9pmrim9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9pmrim9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-solid" /></template>
