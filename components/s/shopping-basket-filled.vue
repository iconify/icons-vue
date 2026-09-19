<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba5wu-bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba5wu-bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-filled" /></template>
