<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u47c1vb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u47c1vb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:truck-delivery-pin" /></template>
