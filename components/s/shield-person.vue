<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3fjcqbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3fjcqbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-person" /></template>
