<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhw43hs6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhw43hs6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:profile-card-solid" /></template>
