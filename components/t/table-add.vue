<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0q9_dbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0q9_dbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:table-add" /></template>
