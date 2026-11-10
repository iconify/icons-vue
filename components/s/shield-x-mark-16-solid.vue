<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj910hkdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bj910hkdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-x-mark-16-solid" /></template>
