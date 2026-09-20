<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egxi5i7oe.css';
import '../../css/e/e8uoipb2s.css';
import '../../css/i/i71zrdbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egxi5i7oe"/><path class="e8uoipb2s"/><path clip-rule="evenodd" class="i71zrdbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paper-clock" /></template>
