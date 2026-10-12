<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdab_2s4t.css';
import '../../css/p/py210wb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdab_2s4t"/><path class="py210wb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paragraph-48" /></template>
