<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_9cgd51r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_9cgd51r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:umbrella-closed-2" /></template>
