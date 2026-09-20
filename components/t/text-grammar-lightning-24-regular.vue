<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iehq34blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-grammar-lightning-24-regular" /></template>
<style>
.iehq34blm {
  fill: currentColor;
  d: path("M12.546 17H2.75l-.102.007A.75.75 0 0 0 2.75 18.5h9.246c0-.211.046-.428.144-.638zm1.175-2.5H2.75a.75.75 0 0 1-.102-1.493L2.75 13h11.676zM21.25 9H2.75l-.102.007A.75.75 0 0 0 2.75 10.5h18.5l.102-.007A.75.75 0 0 0 21.25 9m0-4H2.75l-.102.007A.75.75 0 0 0 2.75 6.5h18.5l.102-.007A.75.75 0 0 0 21.25 5m-4.933 7h4.827a.5.5 0 0 1 .436.745L19.75 16h1.495a.75.75 0 0 1 .565 1.244l-4.824 5.508c-.505.576-1.443.085-1.258-.657L16.5 19h-3.002a.5.5 0 0 1-.453-.713l2.82-6a.5.5 0 0 1 .453-.287");
}

</style>
