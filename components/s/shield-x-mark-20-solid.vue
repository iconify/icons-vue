<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jufx7ibdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jufx7ibdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-x-mark-20-solid" /></template>
