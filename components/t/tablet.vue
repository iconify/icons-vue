<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6b184-4c.css';
import '../../css/k/kv63i2wli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6b184-4c"/><path class="kv63i2wli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:tablet" /></template>
