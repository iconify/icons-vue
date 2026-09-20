<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcunr6bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcunr6bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-star-3" /></template>
