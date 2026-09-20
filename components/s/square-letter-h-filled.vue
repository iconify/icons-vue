<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe4twpbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe4twpbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-h-filled" /></template>
