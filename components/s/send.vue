<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp02o6b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp02o6b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:send" /></template>
