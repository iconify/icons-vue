<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ciq7lht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ciq7lht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:train-solid" /></template>
