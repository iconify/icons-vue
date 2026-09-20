<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8za1g3zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8za1g3zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:person-circle" /></template>
