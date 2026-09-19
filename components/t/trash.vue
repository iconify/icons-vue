<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9yj-ut0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b9yj-ut0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:trash" /></template>
