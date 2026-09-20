<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi_ym-bhd.css';
import '../../css/d/d6kw7zb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_ym-bhd"/><path class="d6kw7zb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sensitive" /></template>
