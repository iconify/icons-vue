<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqnqrx4dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqnqrx4dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mails-solid" /></template>
