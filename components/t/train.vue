<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-kbjab1h.css';
import '../../css/z/z7n6cqbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="z7n6cqbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:train" /></template>
