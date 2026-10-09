<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhixubcci.css';
import '../../css/b/b98id3jfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nhixubcci"/><path class="b98id3jfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:relay-20" /></template>
