<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihbmyisag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihbmyisag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:users" /></template>
