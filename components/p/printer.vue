<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbl60data.css';
import '../../css/t/ty9-8db6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbl60data"/><path class="ty9-8db6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:printer" /></template>
