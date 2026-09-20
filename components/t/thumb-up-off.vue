<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf8klcbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf8klcbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:thumb-up-off" /></template>
