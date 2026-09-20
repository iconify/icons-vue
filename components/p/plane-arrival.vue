<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp6uidzaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp6uidzaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:plane-arrival" /></template>
