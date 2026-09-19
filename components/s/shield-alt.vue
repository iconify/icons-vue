<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxm7xqbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm7xqbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-alt" /></template>
