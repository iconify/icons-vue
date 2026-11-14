<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riogvtbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scissors" /></template>
<style>
.riogvtbrs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 17.5q0-1.536-.629-2.443L12 12.114l2.379 2.943q-.629.907-.629 2.443q0 3.75 3.75 3.75t3.75-3.75t-3.75-3.75q-1.158 0-1.959.358l-2.577-3.187l5.619-6.949q.094-.116.136-.26q.043-.143.027-.291t-.087-.279t-.187-.225q-.058-.047-.123-.081q-.066-.034-.137-.055q-.07-.021-.144-.028t-.147.001t-.144.03t-.135.057t-.122.083t-.103.104L12 9.728l-5.417-6.7q-.094-.116-.225-.187t-.279-.087t-.291.027q-.144.042-.26.136q-.057.046-.104.103q-.048.057-.083.122t-.057.135t-.03.144t-.001.147t.028.144t.055.137t.081.123l5.619 6.949l-2.577 3.187q-.801-.358-1.959-.358q-1.553 0-2.652 1.098Q2.75 15.947 2.75 17.5q0 3.75 3.75 3.75t3.75-3.75");
}

</style>
