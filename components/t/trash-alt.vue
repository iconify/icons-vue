<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0vlk6j2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0vlk6j2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trash-alt" /></template>
