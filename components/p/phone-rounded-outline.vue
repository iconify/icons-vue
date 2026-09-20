<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnnb9e_nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnnb9e_nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-rounded-outline" /></template>
