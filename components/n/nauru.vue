<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpfeuxjdz.css';
import '../../css/j/j33ca7bac.css';
import '../../css/e/et9g0gkeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="cpfeuxjdz"/><path class="j33ca7bac"/><path class="et9g0gkeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:nauru" /></template>
