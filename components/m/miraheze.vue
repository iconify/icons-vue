<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg9mlybdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg9mlybdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:miraheze" /></template>
