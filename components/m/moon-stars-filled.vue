<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2qd5b7pd.css';
import '../../css/a/abf4dkbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2qd5b7pd"/><path class="abf4dkbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-stars-filled" /></template>
