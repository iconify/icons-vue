<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uld0v671t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uld0v671t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:unlink" /></template>
