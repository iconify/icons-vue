<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqikusr0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqikusr0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:watchtower" /></template>
