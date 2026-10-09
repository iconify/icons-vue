<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq5-hnk5f.css';
import '../../css/r/r4lbnxbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eq5-hnk5f"/><path class="r4lbnxbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:table-tennis-20-bold" /></template>
