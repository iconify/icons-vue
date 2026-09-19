<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw99eqe7z.css';
import '../../css/i/ilsfesr3y.css';
import '../../css/u/uaycyrbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jw99eqe7z"/><path class="ilsfesr3y"/><path class="uaycyrbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-outline-alerted" /></template>
