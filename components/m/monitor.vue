<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4wt7sbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4wt7sbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:monitor" /></template>
