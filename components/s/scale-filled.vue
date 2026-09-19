<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoskosbxd.css';
import '../../css/j/j1t29sstw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoskosbxd"/><path class="j1t29sstw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scale-filled" /></template>
