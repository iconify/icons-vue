<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty-u9tbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ty-u9tbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:section-divider-solid" /></template>
