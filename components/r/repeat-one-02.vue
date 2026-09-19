<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnvplibqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnvplibqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:repeat-one-02" /></template>
