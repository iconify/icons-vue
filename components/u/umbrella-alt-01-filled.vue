<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyep2nb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyep2nb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:umbrella-alt-01-filled" /></template>
