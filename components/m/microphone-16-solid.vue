<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1mnhwjrl.css';
import '../../css/a/a311pob4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g1mnhwjrl"/><path class="a311pob4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:microphone-16-solid" /></template>
