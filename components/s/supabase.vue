<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzu0hx63v.css';
import '../../css/o/oo9xgfbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGgmnKNc0g" class="bzu0hx63v"/></defs><use href="#SVGgmnKNc0g"/><use href="#SVGgmnKNc0g"/><path class="oo9xgfbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:supabase" /></template>
