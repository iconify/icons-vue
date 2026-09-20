<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byvv0d4br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byvv0d4br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:simpleiconscdn" /></template>
