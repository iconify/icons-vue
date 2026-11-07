<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udz5nqb7v.css';
import '../../css/k/kdob9slbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path class="kdob9slbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pip-bold-duotone" /></template>
