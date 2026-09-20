<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcifvji8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vcifvji8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:manhole-cover-with-sewage-pipe-cross-section" /></template>
