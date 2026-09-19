<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdnb1nb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdnb1nb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:person-add-outline" /></template>
