<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o46217s1u.css';
import '../../css/r/rzmpwjbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o46217s1u"/><path class="rzmpwjbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:speaker-wave-16-solid" /></template>
