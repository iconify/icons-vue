<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2yj9i4te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2yj9i4te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pipe-24" /></template>
