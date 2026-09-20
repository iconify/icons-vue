<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eahb0bcgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eahb0bcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:section-divider" /></template>
