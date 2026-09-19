<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor-usn7v.css';
import '../../css/k/k91ozubdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b jor-usn7v"/><path class="b k91ozubdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sparkle-square" /></template>
