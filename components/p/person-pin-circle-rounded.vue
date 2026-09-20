<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg2c6mn-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-pin-circle-rounded" /></template>
<style>
.vg2c6mn-f {
  fill: currentColor;
  d: path("M11.53 20.479q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.095-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.198.173-.442.26t-.479.086t-.47-.077M12 9.5q.633 0 1.066-.434Q13.5 8.633 13.5 8t-.434-1.066Q12.633 6.5 12 6.5t-1.066.434T10.5 8t.434 1.066Q11.367 9.5 12 9.5m1.584 4.71q.764-.29 1.374-.854q.125-.106.187-.24q.063-.133.063-.289q0-.236-.118-.423q-.119-.187-.324-.298q-.647-.31-1.352-.458T12 11.5t-1.413.148q-.706.148-1.352.458q-.206.106-.312.292t-.106.404q0 .156.05.29t.175.264q.61.563 1.374.853T12 14.5t1.584-.29");
}

</style>
