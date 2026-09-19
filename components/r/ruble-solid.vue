<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_umz9pvm.css';
import '../../css/f/f5-agqbsi.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 e_umz9pvm"/><path class="clr-i-solid clr-i-solid-path-2 f5-agqbsi"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ruble-solid" /></template>
