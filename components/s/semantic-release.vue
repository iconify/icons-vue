<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg8zgzfkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg8zgzfkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:semantic-release" /></template>
