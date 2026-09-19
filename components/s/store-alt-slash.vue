<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9xwewb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n9xwewb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:store-alt-slash" /></template>
