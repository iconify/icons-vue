<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2y6teb_s.css';
import '../../css/t/tyddiab8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j2y6teb_s"/><path class="tyddiab8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:school-science-test-flask" /></template>
