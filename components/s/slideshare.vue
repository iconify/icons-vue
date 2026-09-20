<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_3gkbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_3gkbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:slideshare" /></template>
