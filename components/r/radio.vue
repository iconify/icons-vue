<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amnh1hbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amnh1hbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radio" /></template>
