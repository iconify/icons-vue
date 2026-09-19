<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh6x7jqib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oh6x7jqib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:person-with-folded-hands-filled" /></template>
