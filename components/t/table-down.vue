<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gir9mfh4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gir9mfh4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-down" /></template>
