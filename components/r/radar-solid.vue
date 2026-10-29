<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi9--gyly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi9--gyly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:radar-solid" /></template>
