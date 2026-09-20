<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r88yrtzkl.css';
import '../../css/a/al9hzkb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r88yrtzkl"/><path class="al9hzkb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:octagon-times" /></template>
