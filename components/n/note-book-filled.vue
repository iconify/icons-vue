<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jdb-d-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3jdb-d-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:note-book-filled" /></template>
