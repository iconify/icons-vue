<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id0ec0buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id0ec0buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:meeple" /></template>
