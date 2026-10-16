<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br5ntsq5m.css';
import '../../css/i/i7r-7htza.css';
import '../../css/j/j2lsbzg7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="br5ntsq5m"/><path class="i7r-7htza"/><path class="j2lsbzg7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:post-office-20" /></template>
