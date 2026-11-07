<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zppc8rbit.css';
import '../../css/f/fmy-1sbhx.css';
import '../../css/o/otzgm8e6s.css';
import '../../css/c/c4oqwbcar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zppc8rbit"/><path class="fmy-1sbhx"/><path class="otzgm8e6s"/><path class="c4oqwbcar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skirt-bold" /></template>
