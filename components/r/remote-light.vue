<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb8t19bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8t19bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:remote-light" /></template>
