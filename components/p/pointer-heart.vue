<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhlgz13bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhlgz13bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-heart" /></template>
