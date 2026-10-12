<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yenqbtb5g.css';
import '../../css/g/ge98ujwjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yenqbtb5g"/><path class="ge98ujwjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-minus-filled" /></template>
