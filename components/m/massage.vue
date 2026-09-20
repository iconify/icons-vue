<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgsghmm9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgsghmm9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:massage" /></template>
