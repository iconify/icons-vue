<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foo-6s4av.css';
import '../../css/e/epzlemb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="foo-6s4av"/><path class="epzlemb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wger" /></template>
