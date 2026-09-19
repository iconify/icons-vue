<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ftoobhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5ftoobhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:maximize-02" /></template>
