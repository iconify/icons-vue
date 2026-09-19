<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k88q8qb5o.css';
import '../../css/o/o250bhbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k88q8qb5o"/><path class="o250bhbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:yunohost" /></template>
