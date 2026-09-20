<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7g6_3buu.css';
import '../../css/g/g-6_fbosi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7g6_3buu"/><path class="g-6_fbosi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ship-1" /></template>
