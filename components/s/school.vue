<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkljblwjh.css';
import '../../css/n/nb72zx0al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkljblwjh"/><path class="nb72zx0al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:school" /></template>
