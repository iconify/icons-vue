<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy2fabb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scooter-outline" /></template>
<style>
.gy2fabb3i {
  fill: currentColor;
  d: path("M19.607 17.578q.412-.403.412-1.001t-.412-1.01t-1.01-.413q-.599 0-1.012.412t-.412 1.011t.413 1.001t1.01.403t1.01-.403M18.597 19q-1.019 0-1.721-.702t-.702-1.721t.702-1.721t1.721-.702q1 0 1.702.702T21 16.577t-.702 1.721t-1.702.702M6.443 17.578q.403-.403.403-1.001t-.403-1.01q-.402-.413-1-.413q-.599 0-1.011.412t-.413 1.011t.413 1.001q.412.403 1.01.403t1.001-.403m-1 1.422q-1.02 0-1.731-.702T3 16.577t.712-1.721t1.73-.702q.874 0 1.524.56q.65.559.82 1.402h5.756q.18-1.687 1.345-2.892t2.817-1.436l-1.439-6.384q-.038-.193-.192-.298Q15.919 5 15.727 5h-3.17V4h3.132q.565 0 1.009.358t.575.904l1.65 7.43h-.327q-1.669 0-2.873 1.147q-1.204 1.146-1.204 2.796v.48H7.787q-.19.824-.85 1.354T5.442 19");
}

</style>
