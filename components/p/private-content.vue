<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-srhgbjw.css';
import '../../css/i/io-ksobwe.css';
import '../../css/d/dhxhj3byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-srhgbjw"/><path class="io-ksobwe"/><path class="dhxhj3byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:private-content" /></template>
