<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5qn53n-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-1.5};
const content = `<path class="b5qn53n-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tools-f" /></template>
