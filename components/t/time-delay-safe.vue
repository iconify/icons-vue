<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hgk_zjbzb"/><path class="k5pw_vigx"/><path class="nh2v95bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-delay-safe" /></template>
<style>
.hgk_zjbzb {
  d: path("M12.2 19H2.5V2.5h19v9.2");
}

.k5pw_vigx {
  d: path("M12.62 11.661q.13-.446.13-.911q0-.16-.016-.319q-.015-.158-.046-.315q-.032-.157-.078-.309q-.046-.153-.107-.301q-.061-.147-.137-.288q-.075-.141-.164-.274q-.088-.132-.19-.256q-.101-.123-.214-.236t-.236-.214q-.124-.102-.256-.19q-.133-.089-.274-.164t-.288-.137q-.148-.061-.301-.107q-.152-.046-.309-.078q-.157-.031-.315-.046Q9.66 7.5 9.5 7.5t-.319.016q-.158.015-.315.046q-.157.032-.309.078q-.153.046-.301.107q-.147.061-.288.137q-.141.075-.274.164q-.132.088-.256.19q-.123.101-.236.214t-.214.236t-.19.256t-.164.274t-.137.288t-.107.301q-.046.152-.078.309q-.031.157-.046.315q-.016.159-.016.319t.016.319q.015.158.046.315q.032.157.078.309q.046.153.107.301q.061.147.137.288q.075.141.164.274q.088.132.19.256q.101.123.214.236t.236.214q.124.102.256.19q.133.089.274.164t.288.137q.148.061.301.107q.152.046.309.078q.157.031.315.046Q9.34 14 9.5 14q.203 0 .404-.025t.398-.075t.385-.125q.189-.074.367-.171q.178-.096.343-.215q.164-.118.313-.256t.279-.293t.24-.326M9.5 10.75h.01M16.5 8.5v3.2M5 19v2.5m10-7h6m-6 7h6m-5-7v1l4 5v1");
}

.nh2v95bix {
  d: path("M20 14.5v1l-4 5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
