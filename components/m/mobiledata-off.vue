<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9m6r4twc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9m6r4twc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mobiledata-off" /></template>
