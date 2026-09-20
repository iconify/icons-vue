<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr9_81qpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr9_81qpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trees" /></template>
